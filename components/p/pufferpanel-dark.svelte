<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg5j9mb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gg5j9mb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pufferpanel-dark" {...props}></Icon>
