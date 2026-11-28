<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5fsocc0g.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/ts44bdc2p.css';
import '../../css/d/d9vkjnbmf.css';
import '../../css/r/rrslsmpft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5fsocc0g secondary"/><g class="dt0cm9dhy primary"><path class="ts44bdc2p"/><path class="d9vkjnbmf"/><path class="rrslsmpft"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cpu-duo" {...props}></Icon>
