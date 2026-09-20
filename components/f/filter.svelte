<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdp5xjw8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="cdp5xjw8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:filter" {...props}></Icon>
