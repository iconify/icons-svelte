<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djuarrb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="djuarrb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:amazon-remix" {...props}></Icon>
