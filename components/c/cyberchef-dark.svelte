<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu9s8wbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gu9s8wbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cyberchef-dark" {...props}></Icon>
