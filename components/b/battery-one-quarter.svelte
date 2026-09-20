<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aftye2b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="aftye2b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:battery-one-quarter" {...props}></Icon>
