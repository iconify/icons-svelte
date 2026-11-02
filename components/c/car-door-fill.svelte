<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k37aljltl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k37aljltl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:car-door-fill" {...props}></Icon>
