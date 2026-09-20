<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghx_bmbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ghx_bmbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:loglynx" {...props}></Icon>
