<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cotn1dbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cotn1dbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ice-cream-cone-filled" {...props}></Icon>
