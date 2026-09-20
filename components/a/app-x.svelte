<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8ortrv8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8ortrv8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:app-x" {...props}></Icon>
