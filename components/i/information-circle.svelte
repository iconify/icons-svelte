<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plrv83b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="plrv83b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:information-circle" {...props}></Icon>
