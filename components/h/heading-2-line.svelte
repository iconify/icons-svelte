<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frf-6rb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frf-6rb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-2-line" {...props}></Icon>
