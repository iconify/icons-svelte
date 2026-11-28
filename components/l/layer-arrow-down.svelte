<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zfzytlb2v.css';
import '../../css/v/vrgoaknvm.css';
import '../../css/s/sa3gq0d8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="zfzytlb2v"/><path class="vrgoaknvm"/><path class="sa3gq0d8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layer-arrow-down" {...props}></Icon>
