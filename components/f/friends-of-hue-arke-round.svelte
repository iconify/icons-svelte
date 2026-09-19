<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2ncilpqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2ncilpqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:friends-of-hue-arke-round" {...props}></Icon>
