<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgp1ggbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cgp1ggbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:remmina-light" {...props}></Icon>
