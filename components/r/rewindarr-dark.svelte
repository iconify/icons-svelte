<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqhc5bcgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pqhc5bcgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rewindarr-dark" {...props}></Icon>
