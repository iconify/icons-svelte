<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtd784ihb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtd784ihb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:arrow-left-circle" {...props}></Icon>
