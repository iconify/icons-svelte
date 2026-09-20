<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq5_t2bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oq5_t2bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:debian" {...props}></Icon>
