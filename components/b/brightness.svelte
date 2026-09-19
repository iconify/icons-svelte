<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxmby0bbg.css';
import '../../css/b/bxhkq1b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lxmby0bbg"/><path class="bxhkq1b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:brightness" {...props}></Icon>
