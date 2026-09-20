<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1vzc6bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1vzc6bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:music-note-line" {...props}></Icon>
