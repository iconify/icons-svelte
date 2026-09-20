<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd2b99bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nd2b99bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-consul-light" {...props}></Icon>
