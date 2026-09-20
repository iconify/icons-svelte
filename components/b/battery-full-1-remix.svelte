<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxff6ebhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hxff6ebhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-full-1-remix" {...props}></Icon>
