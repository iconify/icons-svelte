<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brc0m0l9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brc0m0l9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:map-plus" {...props}></Icon>
