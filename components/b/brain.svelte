<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmd2d0b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmd2d0b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:brain" {...props}></Icon>
