<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv_1knjic.css';
import '../../css/y/yq0zo9bus.css';
import '../../css/e/es3vfqb9k.css';
import '../../css/k/kyr5awbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="bv_1knjic"/><path class="yq0zo9bus"/><path class="es3vfqb9k"/><path class="kyr5awbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:police-car-light" {...props}></Icon>
