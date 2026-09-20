<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az7hstbmu.css';
import '../../css/k/k4z7zsbhp.css';
import '../../css/t/tdhzq11dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><circle class="k4z7zsbhp"/><path class="tdhzq11dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:face-without-mouth" {...props}></Icon>
