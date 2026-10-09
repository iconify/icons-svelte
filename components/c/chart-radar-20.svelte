<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjyhlk1_l.css';
import '../../css/z/zr5giubst.css';
import '../../css/t/tonaopb8e.css';
import '../../css/m/manbawboy.css';
import '../../css/m/m61f7sbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gjyhlk1_l"/><path class="zr5giubst"/><path class="tonaopb8e"/><path class="manbawboy"/><path class="m61f7sbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-radar-20" {...props}></Icon>
