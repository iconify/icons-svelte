<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az7hstbmu.css';
import '../../css/k/kswcaolxm.css';
import '../../css/k/k4z7zsbhp.css';
import '../../css/h/hwmvdgbaf.css';
import '../../css/t/tdhzq11dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><circle class="kswcaolxm"/><circle class="k4z7zsbhp"/><circle class="hwmvdgbaf"/><path class="tdhzq11dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:face-with-open-mouth" {...props}></Icon>
