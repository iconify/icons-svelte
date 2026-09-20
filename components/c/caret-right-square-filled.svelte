<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqc3pmu_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqc3pmu_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:caret-right-square-filled" {...props}></Icon>
