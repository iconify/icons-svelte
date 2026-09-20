<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvoz7pz8e.css';
import '../../css/g/glrhpswps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lvoz7pz8e"/><path class="glrhpswps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:iventoy" {...props}></Icon>
