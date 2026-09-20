<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emlw8mtrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emlw8mtrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chevron-down-circle-filled" {...props}></Icon>
