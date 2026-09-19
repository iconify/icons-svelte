<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhiy7tbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hhiy7tbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:desktopcomputer" {...props}></Icon>
