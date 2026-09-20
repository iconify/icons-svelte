<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yez6l33me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yez6l33me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-diagonal-s-2-fill" {...props}></Icon>
