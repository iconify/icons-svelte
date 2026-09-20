<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2g4ygt8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="c2g4ygt8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:direction-left" {...props}></Icon>
