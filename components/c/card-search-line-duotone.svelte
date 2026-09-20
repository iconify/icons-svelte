<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wr4181b4u.css';
import '../../css/v/vqfns1bta.css';
import '../../css/j/j-a1kqp-o.css';
import '../../css/a/aaakgqotp.css';
import '../../css/i/i8e2akblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wr4181b4u"/><path class="vqfns1bta"/><path class="j-a1kqp-o"/><circle class="aaakgqotp"/><path class="i8e2akblu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-search-line-duotone" {...props}></Icon>
