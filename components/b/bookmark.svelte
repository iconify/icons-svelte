<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w17hi6fgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w17hi6fgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:bookmark" {...props}></Icon>
