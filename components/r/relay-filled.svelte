<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/o/o63_pcrtn.css';
import '../../css/x/x6pji6bmo.css';
import '../../css/w/w33bj_o2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="o63_pcrtn"/><path class="x6pji6bmo"/><path class="w33bj_o2h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:relay-filled" {...props}></Icon>
