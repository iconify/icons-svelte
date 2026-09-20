<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eau72fb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eau72fb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-down-above-nine-eight-eight" {...props}></Icon>
