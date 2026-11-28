<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3ad9nb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="m3ad9nb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:monitor-slash-bold" {...props}></Icon>
