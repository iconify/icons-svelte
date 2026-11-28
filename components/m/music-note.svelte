<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zejnqo3uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zejnqo3uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:music-note" {...props}></Icon>
