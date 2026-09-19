<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/s/suft8gbjr.css';
import '../../css/i/i6mewxbcc.css';
import '../../css/c/cdx5ar_wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="suft8gbjr"/><circle class="i6mewxbcc"/><path class="cdx5ar_wc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:car-alert" {...props}></Icon>
