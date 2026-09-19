<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7vp-0tdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7vp-0tdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:friends-of-hue-arke" {...props}></Icon>
