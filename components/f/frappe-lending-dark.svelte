<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp9n8x0hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sp9n8x0hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-lending-dark" {...props}></Icon>
