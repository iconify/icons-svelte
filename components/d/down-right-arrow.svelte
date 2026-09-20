<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmys1lirk.css';
import '../../css/l/lfy066c5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="lmys1lirk"/><path class="lfy066c5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:down-right-arrow" {...props}></Icon>
