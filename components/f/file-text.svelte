<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reywpyawo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="reywpyawo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:file-text" {...props}></Icon>
