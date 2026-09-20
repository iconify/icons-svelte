<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz9exbb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uz9exbb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-signature-solid" {...props}></Icon>
