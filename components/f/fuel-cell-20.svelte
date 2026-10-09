<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4ztp3ont.css';
import '../../css/w/w093ptm_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u4ztp3ont"/><path class="w093ptm_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-cell-20" {...props}></Icon>
