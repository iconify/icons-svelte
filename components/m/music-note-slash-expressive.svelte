<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by2a68kvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by2a68kvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:music-note-slash-expressive" {...props}></Icon>
