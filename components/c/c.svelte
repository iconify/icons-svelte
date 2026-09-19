<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tk_jupb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="y9tk_jupb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:c" {...props}></Icon>
