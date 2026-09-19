<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6e2wm4vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="i6e2wm4vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-right-circle" {...props}></Icon>
