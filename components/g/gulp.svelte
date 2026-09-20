<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b14xtobke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b14xtobke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:gulp" {...props}></Icon>
