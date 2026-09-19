<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afvvtb2te.css';
import '../../css/l/lxung_xah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="afvvtb2te"/><path class="lxung_xah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-grid-view" {...props}></Icon>
