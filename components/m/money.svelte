<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/n/nz26t1bjz.css';
import '../../css/b/bb9pv_wal.css';
import '../../css/h/h_tsn8bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect class="nz26t1bjz"/><path class="bb9pv_wal"/><circle class="h_tsn8bxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:money" {...props}></Icon>
