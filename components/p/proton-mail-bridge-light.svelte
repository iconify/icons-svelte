<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz2639j6g.css';
import '../../css/r/rulnoebmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lz2639j6g"/><path class="rulnoebmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-mail-bridge-light" {...props}></Icon>
