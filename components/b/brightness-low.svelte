<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6h7psu8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6h7psu8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:brightness-low" {...props}></Icon>
