<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8i-fmzkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k8i-fmzkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:facebook" {...props}></Icon>
