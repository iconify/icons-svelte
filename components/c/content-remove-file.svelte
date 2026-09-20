<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9q2oebck.css';
import '../../css/h/h2jxv96vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x9q2oebck"/><path clip-rule="evenodd" class="h2jxv96vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-remove-file" {...props}></Icon>
