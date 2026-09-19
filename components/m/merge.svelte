<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9_07c7vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i9_07c7vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:merge" {...props}></Icon>
