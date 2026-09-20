<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl4dumkca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hl4dumkca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:artist-song-remix" {...props}></Icon>
