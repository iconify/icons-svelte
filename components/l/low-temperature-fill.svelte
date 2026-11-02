<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfy-2kbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfy-2kbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:low-temperature-fill" {...props}></Icon>
