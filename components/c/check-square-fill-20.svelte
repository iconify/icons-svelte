<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3np0yb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c3np0yb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-square-fill-20" {...props}></Icon>
