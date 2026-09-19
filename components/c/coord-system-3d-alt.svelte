<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx9bvc8de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zx9bvc8de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:coord-system-3d-alt" {...props}></Icon>
