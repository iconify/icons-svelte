<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys6mhwbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys6mhwbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:edit" {...props}></Icon>
