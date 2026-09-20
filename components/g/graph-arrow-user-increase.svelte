<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy9ooh44h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy9ooh44h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:graph-arrow-user-increase" {...props}></Icon>
