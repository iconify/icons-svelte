<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vti80kovh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vti80kovh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:plus-circle-fill-16" {...props}></Icon>
