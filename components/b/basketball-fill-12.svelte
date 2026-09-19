<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re52c97vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="re52c97vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:basketball-fill-12" {...props}></Icon>
