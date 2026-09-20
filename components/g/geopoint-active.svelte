<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-b9rebna.css';
import '../../css/j/j12mv17hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u-b9rebna"/><path class="j12mv17hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:geopoint-active" {...props}></Icon>
