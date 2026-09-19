<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgyg9pbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kgyg9pbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hexagon-vertical-solid" {...props}></Icon>
