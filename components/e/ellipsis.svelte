<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to1fjxbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="to1fjxbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:ellipsis" {...props}></Icon>
