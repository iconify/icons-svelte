<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocf2bv34c.css';
import '../../css/o/ou5xg8k1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ocf2bv34c"/><path class="ou5xg8k1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ghostboard" {...props}></Icon>
