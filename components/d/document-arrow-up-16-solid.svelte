<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duzw7l4-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="duzw7l4-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-arrow-up-16-solid" {...props}></Icon>
