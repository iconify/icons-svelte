<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkyvg6nbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wkyvg6nbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:actionscript" {...props}></Icon>
