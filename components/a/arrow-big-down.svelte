<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1m4_zbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1m4_zbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:arrow-big-down" {...props}></Icon>
