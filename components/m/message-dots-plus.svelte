<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i_nkn0mxa.css';
import '../../css/e/e2y-qsboe.css';
import '../../css/j/jm98hmxlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i_nkn0mxa"/><path class="e2y-qsboe"/><path class="jm98hmxlc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-dots-plus" {...props}></Icon>
