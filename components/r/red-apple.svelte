<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqcr4rb1k.css';
import '../../css/h/hzpiyvrzz.css';
import '../../css/n/nnbxoqbug.css';
import '../../css/x/x5ki1kb4h.css';
import '../../css/h/hf2vh5bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="aqcr4rb1k"/><path class="hzpiyvrzz"/><path class="nnbxoqbug"/><path class="x5ki1kb4h"/><path class="hf2vh5bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:red-apple" {...props}></Icon>
