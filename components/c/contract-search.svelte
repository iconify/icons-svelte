<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2-3w5b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2-3w5b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:contract-search" {...props}></Icon>
