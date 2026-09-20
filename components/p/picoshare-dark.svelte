<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn4u02bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nn4u02bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:picoshare-dark" {...props}></Icon>
