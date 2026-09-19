<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmrl7o3_k.css';
import '../../css/c/clim-4j3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="fmrl7o3_k"/><path class="clim-4j3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-body" {...props}></Icon>
