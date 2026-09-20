<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3-5_c46r.css';
import '../../css/z/z3gsuri1a.css';
import '../../css/w/wqsp95-af.css';
import '../../css/i/ictzck4fu.css';
import '../../css/k/kfkgtizuw.css';
import '../../css/u/uy5am3boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3-5_c46r"/><path class="z3gsuri1a"/><path class="wqsp95-af"/><path class="ictzck4fu"/><path class="kfkgtizuw"/><path class="uy5am3boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:extra" {...props}></Icon>
