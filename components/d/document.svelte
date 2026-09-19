<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akt89zb7w.css';
import '../../css/j/jleau3b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="akt89zb7w"/><path class="jleau3b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:document" {...props}></Icon>
