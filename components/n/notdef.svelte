<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpahkhnhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="bpahkhnhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:notdef" {...props}></Icon>
