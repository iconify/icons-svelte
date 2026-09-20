<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe10_4owo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oe10_4owo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:image-solid" {...props}></Icon>
