<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok_gg1bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ok_gg1bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:connecticut" {...props}></Icon>
