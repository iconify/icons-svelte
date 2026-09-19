<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivj7y7blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ivj7y7blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cube-16-solid" {...props}></Icon>
