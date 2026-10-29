<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6qzu_1jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6qzu_1jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:glasses-solid" {...props}></Icon>
