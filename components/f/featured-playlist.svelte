<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9-r-6e9w.css';
import '../../css/s/s2k9j_-go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s9-r-6e9w"/><path class="s2k9j_-go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:featured-playlist" {...props}></Icon>
