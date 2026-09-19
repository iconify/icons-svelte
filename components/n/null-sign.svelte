<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubmhn9bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ubmhn9bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:null-sign" {...props}></Icon>
