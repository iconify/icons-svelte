<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7k4asbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7k4asbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:plug-x" {...props}></Icon>
