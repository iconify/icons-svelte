<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nasiqcczk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nasiqcczk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-plus-16-solid" {...props}></Icon>
