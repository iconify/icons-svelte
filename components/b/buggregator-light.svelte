<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0064doyk.css';
import '../../css/m/m8qdx0f9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p0064doyk"/><path class="m8qdx0f9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:buggregator-light" {...props}></Icon>
