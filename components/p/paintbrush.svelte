<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy4pt5qrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":32};
const content = `<path class="zy4pt5qrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:paintbrush" {...props}></Icon>
