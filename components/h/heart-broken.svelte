<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lplg4im9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lplg4im9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:heart-broken" {...props}></Icon>
