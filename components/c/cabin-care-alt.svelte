<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yprv9ybsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yprv9ybsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cabin-care-alt" {...props}></Icon>
