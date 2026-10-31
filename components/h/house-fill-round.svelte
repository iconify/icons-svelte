<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llzilzr9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llzilzr9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-fill-round" {...props}></Icon>
