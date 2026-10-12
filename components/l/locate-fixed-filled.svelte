<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_txi0raq.css';
import '../../css/x/xb_-jcbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_txi0raq"/><path clip-rule="evenodd" class="xb_-jcbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:locate-fixed-filled" {...props}></Icon>
