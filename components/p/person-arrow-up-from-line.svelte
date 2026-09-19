<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c94_hxb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="c94_hxb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-arrow-up-from-line" {...props}></Icon>
