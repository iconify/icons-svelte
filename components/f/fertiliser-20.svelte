<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukajkkbxj.css';
import '../../css/y/yep200xlu.css';
import '../../css/l/lem536b_l.css';
import '../../css/e/ee9mz4bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ukajkkbxj"/><path class="yep200xlu"/><path class="lem536b_l"/><path class="ee9mz4bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fertiliser-20" {...props}></Icon>
