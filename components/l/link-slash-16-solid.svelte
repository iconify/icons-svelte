<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc6ou7bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gc6ou7bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:link-slash-16-solid" {...props}></Icon>
