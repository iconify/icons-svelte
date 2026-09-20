<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh62o1bhk.css';
import '../../css/g/g3nrwvb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nh62o1bhk"/><path class="g3nrwvb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:contabo" {...props}></Icon>
