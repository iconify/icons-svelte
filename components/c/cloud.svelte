<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el98ugclt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="el98ugclt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:cloud" {...props}></Icon>
