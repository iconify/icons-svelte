<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-y-g2b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-y-g2b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hard-hat-filled" {...props}></Icon>
