<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx1b0tbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gx1b0tbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:crown" {...props}></Icon>
