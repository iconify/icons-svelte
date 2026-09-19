<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csvj6lbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="csvj6lbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:duolingo" {...props}></Icon>
