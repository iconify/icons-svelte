<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1godd58l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1godd58l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bulletin-board" {...props}></Icon>
