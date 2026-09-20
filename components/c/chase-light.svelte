<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tce8ar49c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tce8ar49c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chase-light" {...props}></Icon>
