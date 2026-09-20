<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy58e45_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zy58e45_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:magnify-with-minus" {...props}></Icon>
