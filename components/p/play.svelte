<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8te-0b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z8te-0b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:play" {...props}></Icon>
