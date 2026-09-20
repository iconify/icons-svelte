<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e63gqob3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e63gqob3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:keyhole-square" {...props}></Icon>
