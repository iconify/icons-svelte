<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d1i2iw-bc.css';
import '../../css/c/c5_8_gb4c.css';
import '../../css/s/s8ub28b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d1i2iw-bc"/><path class="c5_8_gb4c"/><path class="s8ub28b-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-collapse" {...props}></Icon>
