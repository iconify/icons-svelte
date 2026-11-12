<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdrsexbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hdrsexbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chirpy" {...props}></Icon>
