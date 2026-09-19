<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_i0wab7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e_i0wab7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:computer-desktop-16-solid" {...props}></Icon>
