<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyupctqcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":9.12,"height":16};
const content = `<path class="fyupctqcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:pause" {...props}></Icon>
