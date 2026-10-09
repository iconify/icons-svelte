<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elie8f57q.css';
import '../../css/o/ov2o_f2qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="elie8f57q"/><path class="ov2o_f2qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:boiler-20-bold" {...props}></Icon>
