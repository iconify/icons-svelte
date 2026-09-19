<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_i1dsbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i_i1dsbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:duffle-fill" {...props}></Icon>
