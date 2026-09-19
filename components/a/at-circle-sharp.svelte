<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0_a_7k0f.css';
import '../../css/w/wk4cq8krv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e0_a_7k0f"/><path class="wk4cq8krv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:at-circle-sharp" {...props}></Icon>
