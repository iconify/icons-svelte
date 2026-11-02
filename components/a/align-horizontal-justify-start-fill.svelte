<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4n0arbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4n0arbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-horizontal-justify-start-fill" {...props}></Icon>
