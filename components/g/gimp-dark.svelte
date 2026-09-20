<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlqhfn9rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nlqhfn9rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gimp-dark" {...props}></Icon>
