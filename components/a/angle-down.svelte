<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owcch3byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1280};
const content = `<path class="owcch3byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:angle-down" {...props}></Icon>
