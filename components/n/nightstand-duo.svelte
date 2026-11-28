<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4-hdabus.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ag1j6_bzf.css';
import '../../css/u/u-8x-3bpu.css';
import '../../css/m/mtd7yhr0o.css';
import '../../css/a/a6zgemb3a.css';
import '../../css/z/zb63svr9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary u4-hdabus"/><g class="dt0cm9dhy primary"><path class="ag1j6_bzf"/><path class="u-8x-3bpu"/><path class="mtd7yhr0o"/><path class="a6zgemb3a"/><path class="zb63svr9r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:nightstand-duo" {...props}></Icon>
