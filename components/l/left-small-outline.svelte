<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke_s0c99d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ke_s0c99d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:left-small-outline" {...props}></Icon>
