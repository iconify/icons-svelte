<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j5ryysb0v.css';
import '../../css/w/wccisyhhx.css';
import '../../css/g/gupjygfja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j5ryysb0v"/><path class="wccisyhhx"/><path class="gupjygfja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:party-popper" {...props}></Icon>
