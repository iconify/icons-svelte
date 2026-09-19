<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvl9xpv9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pvl9xpv9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-merge-left" {...props}></Icon>
