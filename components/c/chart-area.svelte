<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z61qb2brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z61qb2brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:chart-area" {...props}></Icon>
