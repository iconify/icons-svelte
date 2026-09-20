<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-o72s6ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-o72s6ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:markdown-line" {...props}></Icon>
