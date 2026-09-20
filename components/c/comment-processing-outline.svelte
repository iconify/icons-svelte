<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh-p1r4cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh-p1r4cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-processing-outline" {...props}></Icon>
