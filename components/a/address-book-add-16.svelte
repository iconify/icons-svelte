<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_lwr5nhm.css';
import '../../css/f/flbxrybmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c_lwr5nhm"/><path class="flbxrybmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:address-book-add-16" {...props}></Icon>
