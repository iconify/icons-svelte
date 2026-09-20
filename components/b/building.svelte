<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqwm0ibda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5.5,"top":-2};
const content = `<path class="sqwm0ibda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:building" {...props}></Icon>
