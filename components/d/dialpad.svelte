<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri5cv0bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri5cv0bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:dialpad" {...props}></Icon>
