<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3y2lb35h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="i3y2lb35h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:comment-content" {...props}></Icon>
