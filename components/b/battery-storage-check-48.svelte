<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3j0gtb9o.css';
import '../../css/l/l7s7xcc2s.css';
import '../../css/l/lfph_mk7l.css';
import '../../css/r/r6tthcc7g.css';
import '../../css/z/z4sj3ixdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u3j0gtb9o"/><path class="l7s7xcc2s"/><path class="lfph_mk7l"/><path class="r6tthcc7g"/><path class="z4sj3ixdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-storage-check-48" {...props}></Icon>
