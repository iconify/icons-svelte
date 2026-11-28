<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o2-_brbuv.css';
import '../../css/k/kxz1mg-ky.css';
import '../../css/l/limh9cbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="o2-_brbuv"/><path class="kxz1mg-ky"/><path class="limh9cbhi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:magnet" {...props}></Icon>
