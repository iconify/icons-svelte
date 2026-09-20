<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opky82g8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opky82g8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pets" {...props}></Icon>
