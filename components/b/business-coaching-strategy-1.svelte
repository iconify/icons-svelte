<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7u6b6bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d7u6b6bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:business-coaching-strategy-1" {...props}></Icon>
