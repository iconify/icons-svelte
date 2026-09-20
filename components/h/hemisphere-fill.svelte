<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na23c-lwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na23c-lwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hemisphere-fill" {...props}></Icon>
