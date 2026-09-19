<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx4703bpk.css';
import '../../css/g/gc07aup3p.css';
import '../../css/z/zp2_tubhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fx4703bpk"/><path class="gc07aup3p"/><path class="zp2_tubhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nuxtjs" {...props}></Icon>
