<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s16w2fpog.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sy3k4sw_u.css';
import '../../css/v/vfk79qbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s16w2fpog secondary"/><g class="dt0cm9dhy primary"><path class="sy3k4sw_u"/><path class="vfk79qbjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flag-swallowtail-duo" {...props}></Icon>
