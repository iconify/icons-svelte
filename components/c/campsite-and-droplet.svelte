<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn_ek_m6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kn_ek_m6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-and-droplet" {...props}></Icon>
