<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7f-e8tjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7f-e8tjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-bold-outline" {...props}></Icon>
