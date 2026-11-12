<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1kxjsbic.css';
import '../../css/e/e0vgkpblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1kxjsbic"/><path class="e0vgkpblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-pass-light" {...props}></Icon>
