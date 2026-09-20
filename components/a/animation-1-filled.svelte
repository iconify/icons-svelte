<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezx9wab7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="ezx9wab7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:animation-1-filled" {...props}></Icon>
