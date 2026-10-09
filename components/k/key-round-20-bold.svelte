<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgp4x1bjw.css';
import '../../css/p/p16c5ccou.css';
import '../../css/x/x6y5_jb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pgp4x1bjw"/><path class="p16c5ccou"/><path class="x6y5_jb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:key-round-20-bold" {...props}></Icon>
