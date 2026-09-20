<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1yxcf2mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="v1yxcf2mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flash-2-remix" {...props}></Icon>
