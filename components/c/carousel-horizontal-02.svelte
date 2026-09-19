<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5lc5_hgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5lc5_hgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:carousel-horizontal-02" {...props}></Icon>
