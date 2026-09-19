<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejr4_1b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="ejr4_1b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:media-changer-solid" {...props}></Icon>
