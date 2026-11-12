<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4n_gx7bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="t4n_gx7bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:fluxcd" {...props}></Icon>
