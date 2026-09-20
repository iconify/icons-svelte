<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl1q_wbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl1q_wbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase-variant" {...props}></Icon>
