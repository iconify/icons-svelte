<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysea0pb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysea0pb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:flipkart" {...props}></Icon>
