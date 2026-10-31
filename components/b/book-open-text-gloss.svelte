<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd-u4ybzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd-u4ybzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:book-open-text-gloss" {...props}></Icon>
