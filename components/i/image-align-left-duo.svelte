<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbzx7_b3u.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h5-xafb4k.css';
import '../../css/i/icq-r7o2s.css';
import '../../css/q/qudhafvrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tbzx7_b3u"/><g class="dt0cm9dhy primary"><path class="h5-xafb4k"/><path class="icq-r7o2s"/><path class="qudhafvrj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:image-align-left-duo" {...props}></Icon>
