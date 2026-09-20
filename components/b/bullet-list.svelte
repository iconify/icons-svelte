<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5r3edbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5r3edbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bullet-list" {...props}></Icon>
