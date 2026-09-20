<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st4u3kabo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="st4u3kabo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:add-layer-2-remix" {...props}></Icon>
