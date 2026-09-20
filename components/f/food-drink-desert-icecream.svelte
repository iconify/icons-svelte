<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyx_a2aii.css';
import '../../css/k/kqo6pkb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eyx_a2aii"/><path class="kqo6pkb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:food-drink-desert-icecream" {...props}></Icon>
