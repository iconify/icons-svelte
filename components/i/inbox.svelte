<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlyez0tgf.css';
import '../../css/d/doz4ehbjz.css';
import '../../css/w/wa_6v2bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="wlyez0tgf"/><path class="doz4ehbjz"/><path class="wa_6v2bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:inbox" {...props}></Icon>
