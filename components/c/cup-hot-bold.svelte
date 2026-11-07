<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ld_jb7u.css';
import '../../css/e/e85_kpklm.css';
import '../../css/r/r2y9xybok.css';
import '../../css/l/l5limrb2k.css';
import '../../css/t/tpv95qpsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ld_jb7u"/><path clip-rule="evenodd" class="e85_kpklm"/><path class="r2y9xybok"/><path class="l5limrb2k"/><path class="tpv95qpsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cup-hot-bold" {...props}></Icon>
