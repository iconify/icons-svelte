<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2h8fgbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2h8fgbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:crop-2-line" {...props}></Icon>
