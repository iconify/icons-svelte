<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvcslwbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":32};
const content = `<path clip-rule="evenodd" class="kvcslwbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:docus-light" {...props}></Icon>
