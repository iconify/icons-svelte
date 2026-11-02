<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezpns49_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezpns49_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-pen-line" {...props}></Icon>
