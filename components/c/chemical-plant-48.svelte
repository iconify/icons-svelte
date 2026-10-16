<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrvslrbcn.css';
import '../../css/t/t1ta_fbcc.css';
import '../../css/c/c65-ehvfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qrvslrbcn"/><path class="t1ta_fbcc"/><path class="c65-ehvfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chemical-plant-48" {...props}></Icon>
