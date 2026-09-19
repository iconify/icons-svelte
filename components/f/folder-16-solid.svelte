<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0-5aw7dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r0-5aw7dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-16-solid" {...props}></Icon>
