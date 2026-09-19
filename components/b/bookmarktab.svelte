<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m35bpgbdz.css';
import '../../css/h/hywj0nnlp.css';
import '../../css/d/ddyvihbls.css';
import '../../css/x/xcawsdbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m35bpgbdz"/><path class="hywj0nnlp"/><path class="ddyvihbls"/><path class="xcawsdbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:bookmarktab" {...props}></Icon>
