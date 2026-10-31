<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrqwcb-bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrqwcb-bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:quote-single-right-duotone-round" {...props}></Icon>
