<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztf73cbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ztf73cbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-3-bottom-right-16-solid" {...props}></Icon>
