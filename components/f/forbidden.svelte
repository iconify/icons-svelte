<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggf0qnbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ggf0qnbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:forbidden" {...props}></Icon>
