<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t18qekbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t18qekbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:concierge-bell" {...props}></Icon>
