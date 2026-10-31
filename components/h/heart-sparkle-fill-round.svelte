<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba1_arb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba1_arb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heart-sparkle-fill-round" {...props}></Icon>
