<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dshu0mgqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dshu0mgqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:labview" {...props}></Icon>
