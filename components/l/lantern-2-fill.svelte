<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1ak44dhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1ak44dhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lantern-2-fill" {...props}></Icon>
