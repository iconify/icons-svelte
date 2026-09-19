<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnet24b2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="wnet24b2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:captions-bubble-fill" {...props}></Icon>
