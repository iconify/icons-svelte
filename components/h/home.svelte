<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfib3vzts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfib3vzts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:home" {...props}></Icon>
