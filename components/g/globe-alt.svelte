<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znd8k54cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znd8k54cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-alt" {...props}></Icon>
