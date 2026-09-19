<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2n_4vblw.css';
import '../../css/p/psnhj8bls.css';
import '../../css/c/cauo7_gzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s2n_4vblw"/><path class="psnhj8bls"/><path class="cauo7_gzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-reverse-camera-outline" {...props}></Icon>
