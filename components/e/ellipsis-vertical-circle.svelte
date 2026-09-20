<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th5goy3oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th5goy3oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ellipsis-vertical-circle" {...props}></Icon>
