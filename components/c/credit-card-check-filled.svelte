<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eke7tccoi.css';
import '../../css/p/p8coosbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eke7tccoi"/><path class="p8coosbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:credit-card-check-filled" {...props}></Icon>
