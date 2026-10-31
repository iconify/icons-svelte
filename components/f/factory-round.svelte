<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0hnem5xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0hnem5xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:factory-round" {...props}></Icon>
