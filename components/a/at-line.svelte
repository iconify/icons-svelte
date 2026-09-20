<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc3i_-79p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc3i_-79p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:at-line" {...props}></Icon>
