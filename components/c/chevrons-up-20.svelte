<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8i01qb4b.css';
import '../../css/z/z5m9jtb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n8i01qb4b"/><path class="z5m9jtb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-up-20" {...props}></Icon>
