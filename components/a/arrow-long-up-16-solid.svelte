<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_hzqnb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y_hzqnb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-long-up-16-solid" {...props}></Icon>
