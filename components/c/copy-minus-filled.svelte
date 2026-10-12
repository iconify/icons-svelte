<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xshfpkb5y.css';
import '../../css/u/uwmcnls3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xshfpkb5y"/><path class="uwmcnls3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:copy-minus-filled" {...props}></Icon>
