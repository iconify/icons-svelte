<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zet3uo4bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zet3uo4bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:presentation-play-line" {...props}></Icon>
