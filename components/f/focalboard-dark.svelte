<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgt-rix9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bgt-rix9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:focalboard-dark" {...props}></Icon>
