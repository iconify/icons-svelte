<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd_-5rqcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wd_-5rqcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:paper-clip-16-solid" {...props}></Icon>
