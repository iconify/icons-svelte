<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f30p36brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f30p36brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cilium-tetragon-dark" {...props}></Icon>
