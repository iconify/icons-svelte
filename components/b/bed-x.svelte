<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjb0yu-2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjb0yu-2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bed-x" {...props}></Icon>
