<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh6cq-brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qh6cq-brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-top-bold" {...props}></Icon>
