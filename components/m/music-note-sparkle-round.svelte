<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfyxu1xww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfyxu1xww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:music-note-sparkle-round" {...props}></Icon>
