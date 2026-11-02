<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pardkfbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pardkfbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-open-text-line" {...props}></Icon>
