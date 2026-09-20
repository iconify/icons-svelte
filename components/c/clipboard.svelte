<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r27b-v-yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r27b-v-yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:clipboard" {...props}></Icon>
