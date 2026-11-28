<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf3u8xbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf3u8xbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:heart-crack" {...props}></Icon>
