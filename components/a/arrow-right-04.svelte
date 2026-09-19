<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu-85oigi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu-85oigi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-right-04" {...props}></Icon>
