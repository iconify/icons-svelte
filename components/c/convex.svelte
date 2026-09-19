<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wet55gblz.css';
import '../../css/y/yonkb7w3v.css';
import '../../css/v/v9kz_bb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wet55gblz"/><path class="yonkb7w3v"/><path class="v9kz_bb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:convex" {...props}></Icon>
