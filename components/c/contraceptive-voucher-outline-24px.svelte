<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d6k32obsd.css';
import '../../css/a/ai6bbdefy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d6k32obsd"/><path clip-rule="evenodd" class="ai6bbdefy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:contraceptive-voucher-outline-24px" {...props}></Icon>
