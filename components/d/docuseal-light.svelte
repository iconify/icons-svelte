<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2ee7r-6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p2ee7r-6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docuseal-light" {...props}></Icon>
