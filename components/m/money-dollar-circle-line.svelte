<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_un217oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_un217oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:money-dollar-circle-line" {...props}></Icon>
