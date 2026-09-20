<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p07t8qblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p07t8qblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quetre-light" {...props}></Icon>
