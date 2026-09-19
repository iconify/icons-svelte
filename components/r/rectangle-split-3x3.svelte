<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d73of2b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d73of2b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-split-3x3" {...props}></Icon>
