<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfvex1b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfvex1b1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:location-arrow-outline" {...props}></Icon>
