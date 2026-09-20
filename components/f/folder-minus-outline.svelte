<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cak32ib9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cak32ib9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:folder-minus-outline" {...props}></Icon>
