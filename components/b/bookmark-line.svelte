<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niuy0cbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="niuy0cbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:bookmark-line" {...props}></Icon>
