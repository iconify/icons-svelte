<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozt0eux0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozt0eux0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:command" {...props}></Icon>
