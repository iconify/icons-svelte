<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9x3on9_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f9x3on9_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pickleball-paddle-with-ball" {...props}></Icon>
