<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7flpyn_l.css';
import '../../css/o/ogb69-b7q.css';
import '../../css/q/qcsvf7y1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v7flpyn_l"/><path class="ogb69-b7q"/><path class="qcsvf7y1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blueprint-20-bold" {...props}></Icon>
