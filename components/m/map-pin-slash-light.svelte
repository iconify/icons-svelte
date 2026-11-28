<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9r02achd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i9r02achd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:map-pin-slash-light" {...props}></Icon>
