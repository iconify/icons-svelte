<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pvkc1k-jx.css';
import '../../css/g/gg604n2bm.css';
import '../../css/z/za12y0ykl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pvkc1k-jx"/><path class="gg604n2bm"/><path class="za12y0ykl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-delay-02" {...props}></Icon>
