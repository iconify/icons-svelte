<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cehk_qbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cehk_qbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:calendar-heart" {...props}></Icon>
