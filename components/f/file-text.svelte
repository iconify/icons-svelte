<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8iipjvia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="u8iipjvia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:file-text" {...props}></Icon>
