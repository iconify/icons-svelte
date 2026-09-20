<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_-lzwbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_-lzwbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:repeat-once" {...props}></Icon>
