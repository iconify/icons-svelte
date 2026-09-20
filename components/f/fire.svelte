<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcreuacyk.css';
import '../../css/u/ur8upeb-i.css';
import '../../css/b/bpoy8jcsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="kcreuacyk"/><path class="ur8upeb-i"/><path class="bpoy8jcsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:fire" {...props}></Icon>
