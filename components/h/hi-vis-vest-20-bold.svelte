<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv2slsbxu.css';
import '../../css/g/glkalfxwv.css';
import '../../css/y/ywpb2n2bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uv2slsbxu"/><path class="glkalfxwv"/><path class="ywpb2n2bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hi-vis-vest-20-bold" {...props}></Icon>
