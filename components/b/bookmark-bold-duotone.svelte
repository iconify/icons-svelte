<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts-sbuimt.css';
import '../../css/k/kxlp5qvgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ts-sbuimt"/><path class="kxlp5qvgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-bold-duotone" {...props}></Icon>
