<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gks4ctv1n.css';
import '../../css/m/mk5o0v1xb.css';
import '../../css/s/sua3pvbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="gks4ctv1n"/><path class="mk5o0v1xb"/><path class="sua3pvbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:overview" {...props}></Icon>
