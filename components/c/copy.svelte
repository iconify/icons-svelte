<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b41hdtb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="b41hdtb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:copy" {...props}></Icon>
