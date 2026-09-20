<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf1wvbbac.css';
import '../../css/a/apfxgpb2j.css';
import '../../css/b/bbpzg73-s.css';
import '../../css/j/jpxo32bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="pf1wvbbac"/><path class="apfxgpb2j"/><path paint-order="stroke fill markers" transform="matrix(.6322 .7748 -.7436 .6686 0 0)" class="bbpzg73-s"/><path class="jpxo32bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:dumpling" {...props}></Icon>
