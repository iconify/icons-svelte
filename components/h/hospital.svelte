<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8g3lve1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8g3lve1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:hospital" {...props}></Icon>
