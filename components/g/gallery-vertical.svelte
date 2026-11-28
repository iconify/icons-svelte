<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p8zgc5_5l.css';
import '../../css/v/vc3zpsb3l.css';
import '../../css/w/wwbzjkk7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="p8zgc5_5l"/><path class="vc3zpsb3l"/><path class="wwbzjkk7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gallery-vertical" {...props}></Icon>
