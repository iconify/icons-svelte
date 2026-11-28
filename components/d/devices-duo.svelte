<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mholko41n.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b69dij5rx.css';
import '../../css/m/muxrmeneg.css';
import '../../css/o/oqmofb2lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mholko41n secondary"/><g class="dt0cm9dhy primary"><path class="b69dij5rx"/><path class="muxrmeneg"/><path class="oqmofb2lj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:devices-duo" {...props}></Icon>
