<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m64zwy8rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="m64zwy8rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bow-and-arrow" {...props}></Icon>
