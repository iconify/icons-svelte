<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k46kedfbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k46kedfbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:markdown-fill" {...props}></Icon>
