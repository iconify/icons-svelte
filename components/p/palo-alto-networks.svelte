<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujne8eeaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ujne8eeaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:palo-alto-networks" {...props}></Icon>
