<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwg57p2gj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cwg57p2gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:pause-16-solid" {...props}></Icon>
