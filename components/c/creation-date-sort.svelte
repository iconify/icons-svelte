<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/i/i0xmk6bak.css';
import '../../css/y/y0hfc6mek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path class="i0xmk6bak"/><path class="y0hfc6mek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:creation-date-sort" {...props}></Icon>
