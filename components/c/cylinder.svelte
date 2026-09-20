<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-4boeouc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i-4boeouc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cylinder" {...props}></Icon>
