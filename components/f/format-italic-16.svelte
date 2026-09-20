<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx-eyubof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jx-eyubof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:format-italic-16" {...props}></Icon>
