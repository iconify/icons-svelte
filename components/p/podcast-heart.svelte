<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdrsczb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdrsczb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:podcast-heart" {...props}></Icon>
