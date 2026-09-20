<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzk6pyl2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pzk6pyl2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:lock-2" {...props}></Icon>
