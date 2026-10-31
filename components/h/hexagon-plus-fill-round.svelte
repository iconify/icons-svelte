<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxbmvbc7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxbmvbc7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-plus-fill-round" {...props}></Icon>
