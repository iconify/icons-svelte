<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa2y9obwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xa2y9obwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-right-stroke-12" {...props}></Icon>
