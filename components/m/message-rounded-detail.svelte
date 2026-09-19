<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnx-vib2x.css';
import '../../css/i/irjsvsbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnx-vib2x"/><path class="irjsvsbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:message-rounded-detail" {...props}></Icon>
