<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0zz0d6cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f0zz0d6cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:forward" {...props}></Icon>
