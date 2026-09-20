<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btiw_o-yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="btiw_o-yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:omnom-dark" {...props}></Icon>
