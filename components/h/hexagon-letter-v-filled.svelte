<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3u88lbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3u88lbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-v-filled" {...props}></Icon>
