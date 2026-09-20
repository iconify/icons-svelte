<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbwno_b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pbwno_b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:agentgateway-light" {...props}></Icon>
