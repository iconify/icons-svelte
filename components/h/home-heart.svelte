<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt2ou9bdc.css';
import '../../css/y/yvd4i4bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt2ou9bdc"/><path class="yvd4i4bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:home-heart" {...props}></Icon>
