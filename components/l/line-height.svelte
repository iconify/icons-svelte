<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg11x4bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg11x4bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:line-height" {...props}></Icon>
