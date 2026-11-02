<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um7mmebks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um7mmebks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copper-coin-line" {...props}></Icon>
