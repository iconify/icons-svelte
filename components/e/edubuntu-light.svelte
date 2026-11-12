<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbjad6brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pbjad6brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:edubuntu-light" {...props}></Icon>
