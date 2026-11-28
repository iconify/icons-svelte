<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1zizbche.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1zizbche"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pause-circle" {...props}></Icon>
