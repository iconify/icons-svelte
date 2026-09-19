<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l45hi9gsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="l45hi9gsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:cloud-refresh" {...props}></Icon>
