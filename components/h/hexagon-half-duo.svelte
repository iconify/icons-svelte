<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7_zzsbit.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b00ennbgq.css';
import '../../css/v/vati7obtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7_zzsbit secondary"/><g class="dt0cm9dhy primary"><path class="b00ennbgq"/><path class="vati7obtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hexagon-half-duo" {...props}></Icon>
