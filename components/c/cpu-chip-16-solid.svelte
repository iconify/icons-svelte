<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqsh3o3jo.css';
import '../../css/e/e2-a4zbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iqsh3o3jo"/><path clip-rule="evenodd" class="e2-a4zbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cpu-chip-16-solid" {...props}></Icon>
