<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9wgbmbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d9wgbmbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:argo-cd-light" {...props}></Icon>
