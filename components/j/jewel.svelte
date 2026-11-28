<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n73xqgb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n73xqgb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:jewel" {...props}></Icon>
