<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc68tibjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pc68tibjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:dial" {...props}></Icon>
