<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4a1arbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4a1arbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:rotate-ccw" {...props}></Icon>
