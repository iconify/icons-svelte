<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfrjrd8qn.css';
import '../../css/j/jxfl46bls.css';
import '../../css/h/hfxcmzb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zfrjrd8qn"/><path class="jxfl46bls"/><path class="hfxcmzb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:backbonejs-wordmark" {...props}></Icon>
