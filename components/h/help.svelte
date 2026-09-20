<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2qhwmb-b.css';
import '../../css/n/n0-n86b2f.css';
import '../../css/p/pzrk982qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="k2qhwmb-b"/><path class="n0-n86b2f"/><path class="pzrk982qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:help" {...props}></Icon>
