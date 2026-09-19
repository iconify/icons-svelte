<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/ryzs-efko.css';
import '../../css/v/vm6i8hwdu.css';
import '../../css/w/w276c4mco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ryzs-efko"/><path class="vm6i8hwdu"/><path class="w276c4mco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:baby-bed-02" {...props}></Icon>
