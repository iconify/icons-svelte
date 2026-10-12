<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf_kpfbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yf_kpfbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clock-5-filled" {...props}></Icon>
