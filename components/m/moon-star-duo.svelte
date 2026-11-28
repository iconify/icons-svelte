<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgzmasisn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o0fpmnz7u.css';
import '../../css/p/ph-o_tbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sgzmasisn"/><g class="dt0cm9dhy primary"><path class="o0fpmnz7u"/><path class="ph-o_tbwq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:moon-star-duo" {...props}></Icon>
