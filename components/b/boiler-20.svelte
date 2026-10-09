<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnezarb7y.css';
import '../../css/u/u-fc2jiif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nnezarb7y"/><path class="u-fc2jiif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:boiler-20" {...props}></Icon>
