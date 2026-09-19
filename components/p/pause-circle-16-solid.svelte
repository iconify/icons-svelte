<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4vbgw1nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a4vbgw1nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:pause-circle-16-solid" {...props}></Icon>
