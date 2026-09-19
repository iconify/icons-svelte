<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo5lmccvl.css';
import '../../css/p/p54bnaccc.css';
import '../../css/p/px847tbvl.css';
import '../../css/t/txado3aqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uo5lmccvl"/><path class="p54bnaccc"/><path class="px847tbvl"/><path class="txado3aqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:postgresql" {...props}></Icon>
