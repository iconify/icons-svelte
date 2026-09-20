<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akdc04zlf.css';
import '../../css/a/asob6ykds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="akdc04zlf"/><path class="asob6ykds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:food-drink-hamburger" {...props}></Icon>
