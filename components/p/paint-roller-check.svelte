<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg51h9bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hg51h9bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:paint-roller-check" {...props}></Icon>
