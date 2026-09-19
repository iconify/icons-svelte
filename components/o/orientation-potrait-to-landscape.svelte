<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd5r9rbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd5r9rbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:orientation-potrait-to-landscape" {...props}></Icon>
