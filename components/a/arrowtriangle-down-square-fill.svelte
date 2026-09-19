<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm7raibzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zm7raibzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-down-square-fill" {...props}></Icon>
