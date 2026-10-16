<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tixg4gbgk.css';
import '../../css/o/ox2_dgbyg.css';
import '../../css/c/cgo_eslee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tixg4gbgk"/><path class="ox2_dgbyg"/><path class="cgo_eslee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-search-20" {...props}></Icon>
