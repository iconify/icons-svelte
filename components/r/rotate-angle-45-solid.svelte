<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3srjgb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c3srjgb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:rotate-angle-45-solid" {...props}></Icon>
