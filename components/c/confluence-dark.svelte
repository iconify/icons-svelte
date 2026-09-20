<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snrb6qbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="snrb6qbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:confluence-dark" {...props}></Icon>
