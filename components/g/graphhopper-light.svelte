<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz1dr9udw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hz1dr9udw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:graphhopper-light" {...props}></Icon>
