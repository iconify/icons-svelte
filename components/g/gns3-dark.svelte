<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za_u7lble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="za_u7lble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gns3-dark" {...props}></Icon>
