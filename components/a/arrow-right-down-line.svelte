<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvsh8gd7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvsh8gd7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-down-line" {...props}></Icon>
