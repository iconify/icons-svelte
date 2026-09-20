<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la7tnabna.css';
import '../../css/w/w7blx8bjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="la7tnabna"/><path class="w7blx8bjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:initiative-project-management-dark" {...props}></Icon>
