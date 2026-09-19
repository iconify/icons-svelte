<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw13r8b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw13r8b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:left-luggage" {...props}></Icon>
