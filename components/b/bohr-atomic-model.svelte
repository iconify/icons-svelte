<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_kjfktoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b_kjfktoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bohr-atomic-model" {...props}></Icon>
