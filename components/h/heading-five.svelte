<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er-2y1b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er-2y1b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heading-five" {...props}></Icon>
