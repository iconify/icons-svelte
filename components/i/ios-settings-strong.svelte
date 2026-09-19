<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frn1yib1k.css';
import '../../css/y/y47svzb0n.css';
import '../../css/h/h6c82bcwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="frn1yib1k"/><path class="y47svzb0n"/><path class="h6c82bcwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-settings-strong" {...props}></Icon>
