<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m95anvbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="m95anvbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:belt" {...props}></Icon>
