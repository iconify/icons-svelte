<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sanzdwb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sanzdwb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:media-record-outline" {...props}></Icon>
