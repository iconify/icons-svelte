<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aocoi0bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aocoi0bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-horizontal-justify-center-line" {...props}></Icon>
