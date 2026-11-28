<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/os9nhhb_x.css';
import '../../css/l/lcz2lpl2x.css';
import '../../css/a/adgljtbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="os9nhhb_x"/><path class="lcz2lpl2x"/><path class="adgljtbqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:image-off" {...props}></Icon>
