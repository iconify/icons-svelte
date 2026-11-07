<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cfukg-luk.css';
import '../../css/o/onymejbgu.css';
import '../../css/k/kt1ahab5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cfukg-luk"/><path class="onymejbgu"/><path class="kt1ahab5v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diskette-linear" {...props}></Icon>
