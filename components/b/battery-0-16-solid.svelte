<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykubx6__z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ykubx6__z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:battery-0-16-solid" {...props}></Icon>
