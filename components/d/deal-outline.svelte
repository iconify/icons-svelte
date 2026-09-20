<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_9n7s0do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_9n7s0do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:deal-outline" {...props}></Icon>
