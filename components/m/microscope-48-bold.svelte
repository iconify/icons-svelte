<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9znmuz9h.css';
import '../../css/z/zbnp1eb-z.css';
import '../../css/z/zbd81tbqz.css';
import '../../css/r/r4oyi0vwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c9znmuz9h"/><path class="zbnp1eb-z"/><path class="zbd81tbqz"/><path class="r4oyi0vwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:microscope-48-bold" {...props}></Icon>
