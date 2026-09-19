<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhktsy7zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lhktsy7zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:fire-extinguisher" {...props}></Icon>
