<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlgbxubcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dlgbxubcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:deviantart" {...props}></Icon>
