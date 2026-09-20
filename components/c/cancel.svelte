<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8ghhb29e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8ghhb29e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:cancel" {...props}></Icon>
