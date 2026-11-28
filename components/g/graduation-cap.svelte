<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gozap8bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gozap8bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:graduation-cap" {...props}></Icon>
