<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_60rg5hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_60rg5hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pencil-1" {...props}></Icon>
