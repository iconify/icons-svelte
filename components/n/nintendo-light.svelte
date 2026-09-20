<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9xarfbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o9xarfbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nintendo-light" {...props}></Icon>
