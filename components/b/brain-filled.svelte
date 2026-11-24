<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaq6tmb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xaq6tmb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:brain-filled" {...props}></Icon>
