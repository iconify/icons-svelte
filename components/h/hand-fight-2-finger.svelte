<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bchgvkbbo.css';
import '../../css/c/cy37qpj-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bchgvkbbo"/><path class="cy37qpj-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:hand-fight-2-finger" {...props}></Icon>
