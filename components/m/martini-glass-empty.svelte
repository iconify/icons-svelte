<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq1kgtqzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qq1kgtqzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:martini-glass-empty" {...props}></Icon>
