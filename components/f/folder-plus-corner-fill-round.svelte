<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw7rjbczd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw7rjbczd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-plus-corner-fill-round" {...props}></Icon>
