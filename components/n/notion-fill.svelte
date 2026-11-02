<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q466almew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q466almew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:notion-fill" {...props}></Icon>
