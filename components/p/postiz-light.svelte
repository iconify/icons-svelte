<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw2zm6rod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vw2zm6rod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:postiz-light" {...props}></Icon>
