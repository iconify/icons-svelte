<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxe3iy_vo.css';
import '../../css/b/bi25cle2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qxe3iy_vo"/><path class="bi25cle2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:acquiremock-light" {...props}></Icon>
