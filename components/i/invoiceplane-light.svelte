<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2jubac4c.css';
import '../../css/h/hydjcxbrq.css';
import '../../css/i/iyxxnubym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u2jubac4c"/><path class="hydjcxbrq"/><path class="iyxxnubym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invoiceplane-light" {...props}></Icon>
