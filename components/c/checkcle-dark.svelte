<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw8ww4nck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fw8ww4nck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:checkcle-dark" {...props}></Icon>
