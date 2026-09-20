<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii93tczut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ii93tczut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linkstack-light" {...props}></Icon>
