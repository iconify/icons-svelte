<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y41fw5bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="y41fw5bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:haykal" {...props}></Icon>
