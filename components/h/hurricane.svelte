<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8njocc5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="r8njocc5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hurricane" {...props}></Icon>
