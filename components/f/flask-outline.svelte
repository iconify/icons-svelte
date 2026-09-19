<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8883zb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k8883zb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:flask-outline" {...props}></Icon>
