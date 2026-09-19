<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnn1q3d6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hnn1q3d6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-long-right-16-solid" {...props}></Icon>
