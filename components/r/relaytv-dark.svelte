<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahsrkib1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ahsrkib1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:relaytv-dark" {...props}></Icon>
