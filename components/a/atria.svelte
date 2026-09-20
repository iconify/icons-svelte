<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9618xbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n9618xbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:atria" {...props}></Icon>
