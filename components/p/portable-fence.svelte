<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1fas8u7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j1fas8u7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:portable-fence" {...props}></Icon>
