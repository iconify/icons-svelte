<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orqlr3bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="orqlr3bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-in-water-with-steam" {...props}></Icon>
