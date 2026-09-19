<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnyvk34hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gnyvk34hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-circle-16-solid" {...props}></Icon>
