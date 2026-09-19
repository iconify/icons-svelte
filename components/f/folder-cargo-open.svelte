<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jknxtgxtf.css';
import '../../css/x/xf60uybiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jknxtgxtf"/><path class="xf60uybiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-cargo-open" {...props}></Icon>
