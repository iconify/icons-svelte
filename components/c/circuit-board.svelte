<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/jhxi-trnl.css';
import '../../css/q/qv9zyob3j.css';
import '../../css/n/nol19vq4t.css';
import '../../css/g/g7a-xgufn.css';
import '../../css/h/hzapyruls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="jhxi-trnl"/><path class="qv9zyob3j"/><circle class="nol19vq4t"/><path class="g7a-xgufn"/><circle class="hzapyruls"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:circuit-board" {...props}></Icon>
