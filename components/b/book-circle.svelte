<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzooad_xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tzooad_xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:book-circle" {...props}></Icon>
