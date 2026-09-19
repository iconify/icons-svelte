<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbcgf2hgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbcgf2hgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-stack" {...props}></Icon>
