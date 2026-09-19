<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpn7bkbdx.css';
import '../../css/j/jzqgldrtw.css';
import '../../css/r/r4u10iveo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bpn7bkbdx"/><path class="jzqgldrtw"/><path class="r4u10iveo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:person-with-white-cane" {...props}></Icon>
