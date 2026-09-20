<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtrrq63or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jtrrq63or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frames" {...props}></Icon>
