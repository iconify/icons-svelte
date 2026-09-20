<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k43-1iple.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k43-1iple"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:code-ai" {...props}></Icon>
