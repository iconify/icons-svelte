<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvjw4djzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvjw4djzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:link-3-line" {...props}></Icon>
