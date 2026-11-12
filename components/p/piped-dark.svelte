<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le3-1wb0z.css';
import '../../css/k/kmpx0bclz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="le3-1wb0z"/><path class="kmpx0bclz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:piped-dark" {...props}></Icon>
