<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8tufhvwy.css';
import '../../css/y/y8-ea6dak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x8tufhvwy"/><path class="y8-ea6dak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:direction-rtl-fill-16" {...props}></Icon>
