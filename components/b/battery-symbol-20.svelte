<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u04yhnbuz.css';
import '../../css/d/d7o5e7x9l.css';
import '../../css/p/plrml0c2l.css';
import '../../css/z/zau-730zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u04yhnbuz"/><path class="d7o5e7x9l"/><path class="plrml0c2l"/><path class="zau-730zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-symbol-20" {...props}></Icon>
