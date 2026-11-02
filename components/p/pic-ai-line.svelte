<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkxaukbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkxaukbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pic-ai-line" {...props}></Icon>
