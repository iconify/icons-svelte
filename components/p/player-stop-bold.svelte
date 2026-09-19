<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7yn-bb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="r7yn-bb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-stop-bold" {...props}></Icon>
