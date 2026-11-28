<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p05y_u--y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p05y_u--y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:music-note-plus" {...props}></Icon>
