<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po2tol28y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="po2tol28y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:clipboard-user" {...props}></Icon>
