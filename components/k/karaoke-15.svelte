<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xowwcxs5r.css';
import '../../css/i/is011gbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xowwcxs5r"/><path class="is011gbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:karaoke-15" {...props}></Icon>
