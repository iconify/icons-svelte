<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g53dd3b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="g53dd3b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-20" {...props}></Icon>
