<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4cm5mbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4cm5mbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cached" {...props}></Icon>
