<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b83_sskxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b83_sskxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:media-play-outline" {...props}></Icon>
