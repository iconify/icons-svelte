<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flls6lbhx.css';
import '../../css/j/jatm2wbdf.css';
import '../../css/d/dmqo6kbhf.css';
import '../../css/i/i-m48ibfa.css';
import '../../css/h/hr14dobvu.css';
import '../../css/s/sp_bsk30y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="flls6lbhx"/><path class="jatm2wbdf"/><path class="dmqo6kbhf"/><path class="i-m48ibfa"/><path class="hr14dobvu"/><path class="sp_bsk30y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:cocktailglass" {...props}></Icon>
