<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy-3afbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vy-3afbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:plus-in-circle" {...props}></Icon>
