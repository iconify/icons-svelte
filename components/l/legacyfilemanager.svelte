<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhy_q8b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":896};
const content = `<path class="yhy_q8b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:legacyfilemanager" {...props}></Icon>
