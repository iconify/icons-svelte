<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwkk4ubrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fwkk4ubrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:octopus-deploy-dark" {...props}></Icon>
