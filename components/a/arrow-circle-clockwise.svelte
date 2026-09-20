<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n55x42a9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n55x42a9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-circle-clockwise" {...props}></Icon>
