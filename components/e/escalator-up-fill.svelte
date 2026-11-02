<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs_1f4bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs_1f4bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:escalator-up-fill" {...props}></Icon>
