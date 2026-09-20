<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbtb55bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dbtb55bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:downtify-light" {...props}></Icon>
