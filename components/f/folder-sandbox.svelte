<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5fxn4-5j.css';
import '../../css/w/wqvhhpbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i5fxn4-5j"/><path class="wqvhhpbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-sandbox" {...props}></Icon>
