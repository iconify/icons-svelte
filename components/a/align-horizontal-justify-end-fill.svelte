<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpkmadslo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpkmadslo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-horizontal-justify-end-fill" {...props}></Icon>
