<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp-is2bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fp-is2bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:chevron-back-circle-sharp" {...props}></Icon>
