<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krbfg6bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="krbfg6bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:brotli" {...props}></Icon>
