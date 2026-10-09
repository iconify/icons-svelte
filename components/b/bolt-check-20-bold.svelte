<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilu3h65we.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/j/j7w5exb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ilu3h65we"/><path class="aqsnv9bnd"/><path class="j7w5exb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-check-20-bold" {...props}></Icon>
