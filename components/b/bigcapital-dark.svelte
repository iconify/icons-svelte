<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znep9ab-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="znep9ab-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bigcapital-dark" {...props}></Icon>
