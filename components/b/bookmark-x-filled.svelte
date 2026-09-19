<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm-_mpb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm-_mpb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmark-x-filled" {...props}></Icon>
