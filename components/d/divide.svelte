<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yahd9lb9e.css';
import '../../css/o/ojtwtqbmw.css';
import '../../css/i/iljw3zavc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="yahd9lb9e"/><path class="ojtwtqbmw"/><path class="iljw3zavc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:divide" {...props}></Icon>
