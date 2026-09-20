<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzfvl7dyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tzfvl7dyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dokploy-light" {...props}></Icon>
