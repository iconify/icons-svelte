<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu37ts8tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu37ts8tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-2-bold" {...props}></Icon>
