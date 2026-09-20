<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oni-ybbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oni-ybbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cards-playing-spade-multiple-outline" {...props}></Icon>
