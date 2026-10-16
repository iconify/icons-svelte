<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z33pyccyt.css';
import '../../css/l/lv57wviqe.css';
import '../../css/a/acc7p2d0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z33pyccyt"/><path class="lv57wviqe"/><path class="acc7p2d0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:earth-layers-48" {...props}></Icon>
