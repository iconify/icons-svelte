<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfverpb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gfverpb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:framework" {...props}></Icon>
