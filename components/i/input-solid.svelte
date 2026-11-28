<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_c5r46wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_c5r46wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:input-solid" {...props}></Icon>
