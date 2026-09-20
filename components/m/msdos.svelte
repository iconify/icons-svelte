<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dka_02h5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dka_02h5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:msdos" {...props}></Icon>
