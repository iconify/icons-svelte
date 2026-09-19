<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0qpmvhbh.css';
import '../../css/x/xysj39n-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s0qpmvhbh"/><path class="xysj39n-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:digitalocean" {...props}></Icon>
