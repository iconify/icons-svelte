<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd6vyq9rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="fd6vyq9rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:dehaze" {...props}></Icon>
