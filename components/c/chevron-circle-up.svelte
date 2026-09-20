<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgnmve-ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zgnmve-ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chevron-circle-up" {...props}></Icon>
