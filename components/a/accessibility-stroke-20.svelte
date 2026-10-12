<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyy55sbjn.css';
import '../../css/p/pksro9bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uyy55sbjn"/><path class="pksro9bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:accessibility-stroke-20" {...props}></Icon>
