<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8pgxki_n.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/v-1ltacmn.css';
import '../../css/z/zzco34bep.css';
import '../../css/k/k9pxhyi7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8pgxki_n secondary"/><g class="dt0cm9dhy primary"><path class="v-1ltacmn"/><path class="zzco34bep"/><path class="k9pxhyi7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:foldable-closed-duo" {...props}></Icon>
