<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yraf-tb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="yraf-tb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:ellipsis-vertical-circle" {...props}></Icon>
