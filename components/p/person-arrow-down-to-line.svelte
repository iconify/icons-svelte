<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1muyrb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="u1muyrb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-arrow-down-to-line" {...props}></Icon>
