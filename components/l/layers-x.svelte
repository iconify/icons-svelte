<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4na7gnpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4na7gnpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:layers-x" {...props}></Icon>
