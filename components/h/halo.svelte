<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge4x5w0yg.css';
import '../../css/m/ma50-9zbw.css';
import '../../css/y/yzzk64yza.css';
import '../../css/d/dy4z9objq.css';
import '../../css/x/x3tzy5bjf.css';
import '../../css/q/quasufbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ge4x5w0yg"/><path class="ma50-9zbw"/><path class="yzzk64yza"/><path class="dy4z9objq"/><path class="x3tzy5bjf"/><path class="quasufbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:halo" {...props}></Icon>
