<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpfj5ub0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mpfj5ub0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:docbook" {...props}></Icon>
