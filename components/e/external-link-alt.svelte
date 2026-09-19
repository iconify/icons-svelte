<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf842gvyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uf842gvyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:external-link-alt" {...props}></Icon>
