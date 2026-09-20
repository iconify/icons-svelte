<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwd640c7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwd640c7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-craft" {...props}></Icon>
