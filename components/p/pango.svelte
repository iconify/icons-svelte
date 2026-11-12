<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x153h1baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x153h1baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pango" {...props}></Icon>
