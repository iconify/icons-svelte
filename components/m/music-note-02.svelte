<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyc0af1ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyc0af1ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:music-note-02" {...props}></Icon>
