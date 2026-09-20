<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-n1e2gul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p-n1e2gul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:atera-dark" {...props}></Icon>
