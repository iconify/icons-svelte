<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_dvs5dfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_dvs5dfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:desktop" {...props}></Icon>
