<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emulx1lrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emulx1lrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:lightbulb-star" {...props}></Icon>
