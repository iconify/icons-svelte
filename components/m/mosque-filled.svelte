<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-7w5gbig.css';
import '../../css/y/y1hb6nbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-7w5gbig"/><path class="y1hb6nbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mosque-filled" {...props}></Icon>
