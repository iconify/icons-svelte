<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbfpednqz.css';
import '../../css/u/ug_ur2bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qbfpednqz"/><path class="ug_ur2bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hurricane-48-bold" {...props}></Icon>
