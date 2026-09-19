<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz00iwbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":3200,"height":2048};
const content = `<path class="rz00iwbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:add-reaction" {...props}></Icon>
