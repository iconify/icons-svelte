<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1faat60f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="e1faat60f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:recycle" {...props}></Icon>
