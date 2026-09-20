<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw5c2y68q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="iw5c2y68q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:arrow-circle-right" {...props}></Icon>
