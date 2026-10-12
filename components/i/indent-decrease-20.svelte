<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dus9g0b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dus9g0b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:indent-decrease-20" {...props}></Icon>
