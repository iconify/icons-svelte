<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9iasqb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d9iasqb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mikopbx-dark" {...props}></Icon>
