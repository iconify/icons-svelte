<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j42erew0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j42erew0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrows-up-from-line" {...props}></Icon>
