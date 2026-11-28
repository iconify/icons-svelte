<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c43uy5bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c43uy5bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:group-bold" {...props}></Icon>
