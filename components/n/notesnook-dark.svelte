<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsna-cb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rsna-cb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notesnook-dark" {...props}></Icon>
