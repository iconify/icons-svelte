<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5u1et5dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="b5u1et5dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:quote" {...props}></Icon>
