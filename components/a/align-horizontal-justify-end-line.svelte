<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr5jq2bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr5jq2bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-horizontal-justify-end-line" {...props}></Icon>
