<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swq9uvb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="swq9uvb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apple-light" {...props}></Icon>
