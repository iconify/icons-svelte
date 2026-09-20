<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btnwyabiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="btnwyabiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-bottom-right-to-eight-point-asterisk" {...props}></Icon>
