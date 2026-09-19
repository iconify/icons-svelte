<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e88057bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e88057bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:candy" {...props}></Icon>
