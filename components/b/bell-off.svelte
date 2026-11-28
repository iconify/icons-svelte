<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g--dfv-lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g--dfv-lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bell-off" {...props}></Icon>
