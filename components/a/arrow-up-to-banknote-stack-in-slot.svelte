<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqej7pdcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eqej7pdcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-up-to-banknote-stack-in-slot" {...props}></Icon>
