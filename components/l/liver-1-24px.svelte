<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwnx4pakb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwnx4pakb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:liver-1-24px" {...props}></Icon>
