<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue9mixg-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue9mixg-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:media-play-reverse-outline" {...props}></Icon>
