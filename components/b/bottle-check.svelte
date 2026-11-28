<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ein_ggb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ein_ggb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bottle-check" {...props}></Icon>
