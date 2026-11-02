<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnzi7lzqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnzi7lzqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-big-left-dash-line" {...props}></Icon>
