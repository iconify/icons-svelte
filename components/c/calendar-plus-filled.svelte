<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3c95uabp.css';
import '../../css/u/upue2acrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3c95uabp"/><path class="upue2acrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-plus-filled" {...props}></Icon>
