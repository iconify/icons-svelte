<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqmbxsbsp.css';
import '../../css/x/xefnkubua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fqmbxsbsp"/><path class="xefnkubua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:metabase" {...props}></Icon>
