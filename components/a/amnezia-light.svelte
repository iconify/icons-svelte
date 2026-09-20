<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v78_twb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v78_twb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amnezia-light" {...props}></Icon>
