<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhvui9tfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jhvui9tfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:doc-append" {...props}></Icon>
