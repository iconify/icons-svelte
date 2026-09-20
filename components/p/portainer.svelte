<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp3f46b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wp3f46b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:portainer" {...props}></Icon>
