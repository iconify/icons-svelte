<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c79n5y3hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="c79n5y3hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:plane" {...props}></Icon>
