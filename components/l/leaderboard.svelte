<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w860uf_8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w860uf_8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:leaderboard" {...props}></Icon>
