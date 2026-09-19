<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfzvm7b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfzvm7b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:carousel-horizontal" {...props}></Icon>
