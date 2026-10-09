<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbo2x6civ.css';
import '../../css/a/a-b9sjb0f.css';
import '../../css/r/roiba_3fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jbo2x6civ"/><path class="a-b9sjb0f"/><path class="roiba_3fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plant-20-bold" {...props}></Icon>
