<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ark4w8oht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ark4w8oht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:paint-brush-16-solid" {...props}></Icon>
