<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moapas8xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moapas8xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:face-surprised" {...props}></Icon>
