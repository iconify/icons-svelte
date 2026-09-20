<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzphs4bvs.css';
import '../../css/b/b-rxk4bpv.css';
import '../../css/p/prjehr37f.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/f/fcu35bc_a.css';
import '../../css/z/zaqnsm2le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="xzphs4bvs"/><path class="b-rxk4bpv"/><path class="prjehr37f"/><g class="jn8qy4bru"><path class="fcu35bc_a"/><path class="zaqnsm2le"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:horse" {...props}></Icon>
