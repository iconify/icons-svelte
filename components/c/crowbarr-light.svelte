<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt5h2-4uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lt5h2-4uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crowbarr-light" {...props}></Icon>
