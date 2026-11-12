<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni_g83x2x.css';
import '../../css/a/a4a1azmng.css';
import '../../css/g/g11ghhn1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ni_g83x2x"/><path class="a4a1azmng"/><path class="g11ghhn1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:redis-dark" {...props}></Icon>
