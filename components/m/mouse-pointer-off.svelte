<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i27q8j8lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i27q8j8lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-pointer-off" {...props}></Icon>
