<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbwv8vb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbwv8vb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-right-square-solid" {...props}></Icon>
