<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcwpt2h2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mcwpt2h2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:fire-16-solid" {...props}></Icon>
