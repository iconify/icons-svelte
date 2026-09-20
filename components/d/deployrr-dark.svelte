<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs6zkkb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xs6zkkb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:deployrr-dark" {...props}></Icon>
