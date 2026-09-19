<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5f5msbrf.css';
import '../../css/d/dx3032ngj.css';
import '../../css/i/ibbuc4bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d5f5msbrf"/><path class="dx3032ngj"/><path class="ibbuc4bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:performingarts" {...props}></Icon>
