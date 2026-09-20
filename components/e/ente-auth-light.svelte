<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn-2fcubd.css';
import '../../css/c/cia5ouwnr.css';
import '../../css/v/vu75sh_8v.css';
import '../../css/a/a5ynwdbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bn-2fcubd"/><path class="cia5ouwnr"/><path class="vu75sh_8v"/><path class="a5ynwdbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ente-auth-light" {...props}></Icon>
