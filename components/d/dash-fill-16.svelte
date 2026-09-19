<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiv9lxbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tiv9lxbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:dash-fill-16" {...props}></Icon>
