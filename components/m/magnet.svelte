<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys5db5b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys5db5b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:magnet" {...props}></Icon>
