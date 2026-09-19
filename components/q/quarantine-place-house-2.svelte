<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tfmtz425a.css';
import '../../css/t/tm2l-nbzh.css';
import '../../css/k/kugbtdbkv.css';
import '../../css/l/l4nf9kbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="tfmtz425a"/><path class="tm2l-nbzh"/><path class="kugbtdbkv"/><path class="l4nf9kbry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:quarantine-place-house-2" {...props}></Icon>
