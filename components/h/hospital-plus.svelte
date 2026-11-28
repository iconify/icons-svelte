<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl5q3r92p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl5q3r92p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hospital-plus" {...props}></Icon>
