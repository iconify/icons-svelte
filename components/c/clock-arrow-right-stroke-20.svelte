<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlijh8b1j.css';
import '../../css/z/z-s_bkbrl.css';
import '../../css/n/n1_wm9fxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zlijh8b1j"/><path class="z-s_bkbrl"/><path class="n1_wm9fxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-arrow-right-stroke-20" {...props}></Icon>
