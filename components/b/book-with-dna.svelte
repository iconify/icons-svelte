<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv3ahtb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fv3ahtb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-dna" {...props}></Icon>
