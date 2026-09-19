<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b90k02bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="b90k02bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:alignverticalcenter" {...props}></Icon>
