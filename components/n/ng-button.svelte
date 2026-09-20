<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnsv-_bix.css';
import '../../css/n/n81tx26mw.css';
import '../../css/f/f-y67rbmu.css';
import '../../css/v/vngdzxbyc.css';
import '../../css/e/ed86nmtzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="mnsv-_bix"/><g class="n81tx26mw"><path class="f-y67rbmu"/><path class="vngdzxbyc"/></g><path class="ed86nmtzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:ng-button" {...props}></Icon>
