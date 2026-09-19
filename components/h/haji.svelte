<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sbieo1jys.css';
import '../../css/p/p7cl2h8tx.css';
import '../../css/j/jsjl7cbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sbieo1jys"/><path class="p7cl2h8tx"/><path class="jsjl7cbxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:haji" {...props}></Icon>
