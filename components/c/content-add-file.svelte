<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9q2oebck.css';
import '../../css/c/cw4dc9bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x9q2oebck"/><path clip-rule="evenodd" class="cw4dc9bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-add-file" {...props}></Icon>
