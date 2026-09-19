<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4mkgjboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":541,"height":730};
const content = `<path class="y4mkgjboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:asciicircum" {...props}></Icon>
