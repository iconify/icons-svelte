<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1qhulkfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1qhulkfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:presentation-times" {...props}></Icon>
