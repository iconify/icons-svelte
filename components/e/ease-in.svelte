<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix9b12bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ix9b12bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:ease-in" {...props}></Icon>
