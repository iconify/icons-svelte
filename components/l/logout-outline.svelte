<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiirhsbnc.css';
import '../../css/k/k-ib4_rmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iiirhsbnc"/><path clip-rule="evenodd" class="k-ib4_rmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:logout-outline" {...props}></Icon>
