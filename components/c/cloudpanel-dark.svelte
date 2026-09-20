<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2hy-na5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r2hy-na5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudpanel-dark" {...props}></Icon>
