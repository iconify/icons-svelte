<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxmzs5b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hxmzs5b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ironmount-dark" {...props}></Icon>
