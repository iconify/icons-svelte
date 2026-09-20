<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hca6g4gme.css';
import '../../css/m/mtjf1dn9k.css';
import '../../css/k/ksw0hwbel.css';
import '../../css/u/u_znmv-9h.css';
import '../../css/w/whp-25b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="hca6g4gme"/><path class="mtjf1dn9k"/><path class="ksw0hwbel"/><path clip-rule="evenodd" class="u_znmv-9h"/><path class="whp-25b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:markdown" {...props}></Icon>
