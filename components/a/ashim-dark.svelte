<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iebr1bctr.css';
import '../../css/p/p1mbpccli.css';
import '../../css/e/e3l4mac6w.css';
import '../../css/i/il-pnhbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iebr1bctr"/><path class="p1mbpccli"/><path class="e3l4mac6w"/><path class="il-pnhbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ashim-dark" {...props}></Icon>
