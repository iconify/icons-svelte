<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnv6cykfw.css';
import '../../css/j/jjf3s4bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnv6cykfw"/><path class="jjf3s4bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:blender" {...props}></Icon>
