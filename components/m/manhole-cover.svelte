<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx-9cq0ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fx-9cq0ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:manhole-cover" {...props}></Icon>
