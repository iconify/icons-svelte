<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9rc97b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9rc97b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:calendar-edit" {...props}></Icon>
