<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccb5m9byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ccb5m9byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document-settings" {...props}></Icon>
