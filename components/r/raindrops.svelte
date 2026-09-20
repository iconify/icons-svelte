<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0a8dc52p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0a8dc52p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:raindrops" {...props}></Icon>
