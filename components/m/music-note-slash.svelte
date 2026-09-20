<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b731rmehh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b731rmehh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:music-note-slash" {...props}></Icon>
