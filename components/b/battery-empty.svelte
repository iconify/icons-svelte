<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmemd-bvx.css';
import '../../css/a/as_el_bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qmemd-bvx"/><path class="as_el_bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:battery-empty" {...props}></Icon>
