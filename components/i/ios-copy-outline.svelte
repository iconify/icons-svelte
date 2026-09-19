<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhnf1kbvb.css';
import '../../css/c/ccs4fgbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rhnf1kbvb"/><path class="ccs4fgbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-copy-outline" {...props}></Icon>
