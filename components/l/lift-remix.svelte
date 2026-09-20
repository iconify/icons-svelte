<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2h002-cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a2h002-cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:lift-remix" {...props}></Icon>
