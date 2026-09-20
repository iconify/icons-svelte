<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3w_inz3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f3w_inz3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:music-note-2-solid" {...props}></Icon>
