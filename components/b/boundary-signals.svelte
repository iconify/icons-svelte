<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pulc08b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pulc08b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:boundary-signals" {...props}></Icon>
