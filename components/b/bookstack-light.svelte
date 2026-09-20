<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viz9rp2hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="viz9rp2hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bookstack-light" {...props}></Icon>
