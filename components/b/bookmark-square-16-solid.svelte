<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfp7kbbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pfp7kbbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bookmark-square-16-solid" {...props}></Icon>
