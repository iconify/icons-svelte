<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr1tfnb7u.css';
import '../../css/r/r73_lp1xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xr1tfnb7u"/><path class="r73_lp1xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:import-16" {...props}></Icon>
