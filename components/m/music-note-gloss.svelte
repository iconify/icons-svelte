<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sej40yb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sej40yb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:music-note-gloss" {...props}></Icon>
