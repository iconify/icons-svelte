<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9yemybjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9yemybjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:content-ai-fill" {...props}></Icon>
