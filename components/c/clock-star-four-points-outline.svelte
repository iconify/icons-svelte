<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6hitmb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6hitmb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-star-four-points-outline" {...props}></Icon>
