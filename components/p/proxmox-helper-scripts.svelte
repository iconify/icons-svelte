<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzec-gbac.css';
import '../../css/f/ff2dlhbix.css';
import '../../css/a/a7--3wfxj.css';
import '../../css/a/at489ww4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kzec-gbac"/><path class="ff2dlhbix"/><path class="a7--3wfxj"/><path class="at489ww4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proxmox-helper-scripts" {...props}></Icon>
