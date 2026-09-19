<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5yzg4h-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d5yzg4h-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-hackernews" {...props}></Icon>
