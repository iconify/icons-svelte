<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1rj3bivm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n1rj3bivm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:format-underline-16" {...props}></Icon>
