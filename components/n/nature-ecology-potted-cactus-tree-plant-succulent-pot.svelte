<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irmgkn-rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="irmgkn-rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:nature-ecology-potted-cactus-tree-plant-succulent-pot" {...props}></Icon>
