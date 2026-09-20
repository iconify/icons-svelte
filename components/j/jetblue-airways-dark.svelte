<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1va1ac7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b1va1ac7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jetblue-airways-dark" {...props}></Icon>
