<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esa26dzqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esa26dzqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:railroad-metro-bold" {...props}></Icon>
