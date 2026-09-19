<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usc5tqbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usc5tqbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:music-double-note-add" {...props}></Icon>
