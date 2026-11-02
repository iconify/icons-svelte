<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epxcznbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epxcznbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-check-2-fill" {...props}></Icon>
