<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9zln_13e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9zln_13e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dish-cover-line" {...props}></Icon>
