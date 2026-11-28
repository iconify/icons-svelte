<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrs790btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrs790btu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:dashboard-gear" {...props}></Icon>
