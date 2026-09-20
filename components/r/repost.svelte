<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktl-3pzor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktl-3pzor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:repost" {...props}></Icon>
