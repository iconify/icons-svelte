<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztw2c0b2i.css';
import '../../css/u/u_7ar5bnj.css';
import '../../css/b/bsnu2pbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ztw2c0b2i"/><path clip-rule="evenodd" class="u_7ar5bnj"/><path class="bsnu2pbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:lan-cable-solid" {...props}></Icon>
