<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3js9ckvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3js9ckvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-broken" {...props}></Icon>
