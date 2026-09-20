<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm8yzh27k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gm8yzh27k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-rocket" {...props}></Icon>
