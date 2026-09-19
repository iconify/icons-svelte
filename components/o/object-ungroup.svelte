<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwmnbk0gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1792};
const content = `<path class="xwmnbk0gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:object-ungroup" {...props}></Icon>
