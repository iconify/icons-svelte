<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7_udwd8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e7_udwd8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-right-start-on-rectangle-16-solid" {...props}></Icon>
