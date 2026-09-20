<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u01ibdujt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u01ibdujt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:midjourney-dark" {...props}></Icon>
