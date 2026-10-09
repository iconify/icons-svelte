<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz2bs4vlk.css';
import '../../css/e/ej03xab5i.css';
import '../../css/u/u3lzsvbcn.css';
import '../../css/x/xoa7shbml.css';
import '../../css/w/wrdg80bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rz2bs4vlk"/><path class="ej03xab5i"/><path class="u3lzsvbcn"/><path class="xoa7shbml"/><path class="wrdg80bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:methane-20-bold" {...props}></Icon>
