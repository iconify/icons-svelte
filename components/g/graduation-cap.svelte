<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7dw4obsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7dw4obsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:graduation-cap" {...props}></Icon>
