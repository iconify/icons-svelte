<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfaj228ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rfaj228ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:cercle-2" {...props}></Icon>
