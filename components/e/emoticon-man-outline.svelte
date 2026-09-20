<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sussbubbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sussbubbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoticon-man-outline" {...props}></Icon>
