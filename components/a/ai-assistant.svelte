<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-sv72byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-sv72byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:ai-assistant" {...props}></Icon>
