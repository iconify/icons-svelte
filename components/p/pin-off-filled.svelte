<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brilosa1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brilosa1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pin-off-filled" {...props}></Icon>
