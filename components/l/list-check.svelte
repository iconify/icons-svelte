<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqo96s-5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqo96s-5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:list-check" {...props}></Icon>
