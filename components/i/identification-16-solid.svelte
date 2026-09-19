<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiklxfb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uiklxfb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:identification-16-solid" {...props}></Icon>
