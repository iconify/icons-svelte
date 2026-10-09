<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shrshrltt.css';
import '../../css/j/jqow3gbkz.css';
import '../../css/e/euu9n8cdz.css';
import '../../css/x/x_1wshpcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="shrshrltt"/><path class="jqow3gbkz"/><path class="euu9n8cdz"/><path class="x_1wshpcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plant-pot-20-bold" {...props}></Icon>
