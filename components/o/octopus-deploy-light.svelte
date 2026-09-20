<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2mtu7rth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h2mtu7rth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:octopus-deploy-light" {...props}></Icon>
