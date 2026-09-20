<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua5uh7bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua5uh7bgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:numbers-09-sort-descending-fill" {...props}></Icon>
