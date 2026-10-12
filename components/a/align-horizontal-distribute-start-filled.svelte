<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foz5q4n-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="foz5q4n-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-horizontal-distribute-start-filled" {...props}></Icon>
