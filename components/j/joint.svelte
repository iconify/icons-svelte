<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2pkaxbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j2pkaxbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:joint" {...props}></Icon>
