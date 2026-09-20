<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_-3hmxfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f_-3hmxfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librewolf-light" {...props}></Icon>
