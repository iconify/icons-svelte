<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjrqzlcft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjrqzlcft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:fastapi" {...props}></Icon>
