<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6xhkvgef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6xhkvgef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:corner-right-up-line" {...props}></Icon>
