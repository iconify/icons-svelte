<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1ut0ub3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b1ut0ub3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fish-beside-sausage" {...props}></Icon>
