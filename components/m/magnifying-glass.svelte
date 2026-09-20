<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uko8rh9_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="uko8rh9_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:magnifying-glass" {...props}></Icon>
