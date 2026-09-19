<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2xskwu5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2xskwu5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rooms-hallway" {...props}></Icon>
