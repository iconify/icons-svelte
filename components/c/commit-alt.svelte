<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8gw94rgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c8gw94rgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:commit-alt" {...props}></Icon>
