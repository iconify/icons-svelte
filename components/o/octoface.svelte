<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laysg3b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="laysg3b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:octoface" {...props}></Icon>
