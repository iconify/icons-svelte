<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_2dczbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k_2dczbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:receipt-japanese-yen-filled" {...props}></Icon>
