<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm6wdobjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tm6wdobjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openproject-light" {...props}></Icon>
