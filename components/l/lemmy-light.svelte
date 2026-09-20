<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndwbrqb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ndwbrqb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lemmy-light" {...props}></Icon>
