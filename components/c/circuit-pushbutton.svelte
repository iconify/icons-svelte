<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i372fibbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i372fibbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circuit-pushbutton" {...props}></Icon>
