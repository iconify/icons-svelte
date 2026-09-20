<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_q_12zeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_q_12zeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-9-plus-box-multiple" {...props}></Icon>
