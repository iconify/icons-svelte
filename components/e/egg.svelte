<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saj0lv78a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="saj0lv78a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:egg" {...props}></Icon>
