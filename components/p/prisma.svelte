<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irmk_pbcb.css';
import '../../css/z/zpt2lgb4a.css';
import '../../css/r/rpp_nsbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="irmk_pbcb"/><path class="zpt2lgb4a"/><path class="rpp_nsbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:prisma" {...props}></Icon>
