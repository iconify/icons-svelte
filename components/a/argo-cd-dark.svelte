<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5kud9bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h5kud9bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:argo-cd-dark" {...props}></Icon>
