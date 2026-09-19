<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/ucxrrm7vu.css';
import '../../css/i/iyvxh6bma.css';
import '../../css/e/epb3e3v_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ucxrrm7vu"/><path class="iyvxh6bma"/><path class="epb3e3v_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:burj-al-arab" {...props}></Icon>
