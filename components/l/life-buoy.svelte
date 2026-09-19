<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuzwqwb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="zuzwqwb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:life-buoy" {...props}></Icon>
