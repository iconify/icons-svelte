<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1oqwq31l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d1oqwq31l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:cogs" {...props}></Icon>
