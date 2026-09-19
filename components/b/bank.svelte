<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5a8f4ihf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z5a8f4ihf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:bank" {...props}></Icon>
