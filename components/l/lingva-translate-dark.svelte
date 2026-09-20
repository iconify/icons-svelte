<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv0x2jbvr.css';
import '../../css/x/xsuq0vbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fv0x2jbvr"/><path class="xsuq0vbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lingva-translate-dark" {...props}></Icon>
