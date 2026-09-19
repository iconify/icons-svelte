<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa_ew7b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa_ew7b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ham" {...props}></Icon>
