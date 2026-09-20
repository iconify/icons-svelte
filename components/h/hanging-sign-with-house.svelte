<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4puocchg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z4puocchg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hanging-sign-with-house" {...props}></Icon>
