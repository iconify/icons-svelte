<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_lxzxuvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="u_lxzxuvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:blender-phone" {...props}></Icon>
