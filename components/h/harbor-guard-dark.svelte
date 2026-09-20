<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3se15b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k3se15b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:harbor-guard-dark" {...props}></Icon>
