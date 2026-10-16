<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oku93bowu.css';
import '../../css/p/p2-gc3lvi.css';
import '../../css/n/nzvyk8_7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oku93bowu"/><path class="p2-gc3lvi"/><path class="nzvyk8_7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-search-48-bold" {...props}></Icon>
