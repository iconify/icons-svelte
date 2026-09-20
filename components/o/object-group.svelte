<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqyr_1b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqyr_1b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:object-group" {...props}></Icon>
