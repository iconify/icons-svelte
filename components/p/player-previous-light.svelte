<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1223mbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1223mbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-previous-light" {...props}></Icon>
