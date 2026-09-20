<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2u1i6b4l.css';
import '../../css/h/h_pt1abna.css';
import '../../css/m/ma684bb2g.css';
import '../../css/e/e4zfowz9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="u2u1i6b4l"/><path class="h_pt1abna"/><path class="ma684bb2g"/><path class="e4zfowz9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:aries" {...props}></Icon>
