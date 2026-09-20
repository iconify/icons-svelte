<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbkny492m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbkny492m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:media-fast-forward-outline" {...props}></Icon>
