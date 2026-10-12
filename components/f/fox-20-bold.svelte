<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjy23_bwm.css';
import '../../css/e/ex-8_4bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cjy23_bwm"/><path class="ex-8_4bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fox-20-bold" {...props}></Icon>
