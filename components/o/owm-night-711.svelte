<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d00ah8b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="d00ah8b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-night-711" {...props}></Icon>
