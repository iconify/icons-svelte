<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lff_3fe-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lff_3fe-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pentagon" {...props}></Icon>
