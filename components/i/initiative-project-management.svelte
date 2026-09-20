<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dee-53fyq.css';
import '../../css/p/pjju7xbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dee-53fyq"/><path class="pjju7xbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:initiative-project-management" {...props}></Icon>
