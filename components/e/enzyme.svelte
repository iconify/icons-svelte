<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyognab8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tyognab8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:enzyme" {...props}></Icon>
