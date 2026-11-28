<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjkn40but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjkn40but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:megaphone-check" {...props}></Icon>
