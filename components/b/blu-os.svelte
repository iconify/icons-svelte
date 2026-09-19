<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry_r6gbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry_r6gbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:blu-os" {...props}></Icon>
