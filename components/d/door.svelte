<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h0tq4hvtq.css';
import '../../css/y/y9va7ujcs.css';
import '../../css/l/lua2tfd8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="h0tq4hvtq"/><path class="y9va7ujcs"/><path class="lua2tfd8g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:door" {...props}></Icon>
