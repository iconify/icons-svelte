<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p74ref19a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p74ref19a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:media-stop-outline" {...props}></Icon>
