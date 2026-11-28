<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs7ot4bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs7ot4bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cable-car-clock" {...props}></Icon>
