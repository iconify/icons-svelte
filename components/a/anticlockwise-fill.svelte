<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq7dv5egz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq7dv5egz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:anticlockwise-fill" {...props}></Icon>
