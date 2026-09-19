<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc667f1qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kc667f1qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrows-pointing-out-16-solid" {...props}></Icon>
