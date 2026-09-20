<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxql92bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xxql92bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:pencil" {...props}></Icon>
