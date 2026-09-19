<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b72-nxbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="b72-nxbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:bookmark" {...props}></Icon>
