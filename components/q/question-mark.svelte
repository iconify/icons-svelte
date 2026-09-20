<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk136onmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lk136onmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:question-mark" {...props}></Icon>
