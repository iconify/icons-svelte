<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_8f4bb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_8f4bb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-off" {...props}></Icon>
