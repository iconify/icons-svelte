<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoifu0ksb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qoifu0ksb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-4-ai-line" {...props}></Icon>
