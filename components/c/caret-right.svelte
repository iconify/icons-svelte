<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0xtwtpgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j0xtwtpgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:caret-right" {...props}></Icon>
