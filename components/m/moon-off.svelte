<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj1yuh1cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj1yuh1cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:moon-off" {...props}></Icon>
